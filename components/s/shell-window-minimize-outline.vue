<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aucf8sb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aucf8sb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:shell-window-minimize-outline" /></template>
