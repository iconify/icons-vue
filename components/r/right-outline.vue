<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf8p51b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bf8p51b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:right-outline" /></template>
