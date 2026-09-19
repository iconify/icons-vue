<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6p7f05an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="j6p7f05an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:mobile-phone-alt2" /></template>
