<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npfsumi_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="npfsumi_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:tray" /></template>
