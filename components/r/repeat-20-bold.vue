<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmh3e9bdx.css';
import '../../css/z/z_yq7-buc.css';
import '../../css/y/yg_0l029v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wmh3e9bdx"/><path class="z_yq7-buc"/><path class="yg_0l029v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:repeat-20-bold" /></template>
