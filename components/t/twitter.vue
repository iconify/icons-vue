<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffd_xfbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ffd_xfbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:twitter" /></template>
