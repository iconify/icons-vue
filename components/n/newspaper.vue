<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jebob6j0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jebob6j0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:newspaper" /></template>
