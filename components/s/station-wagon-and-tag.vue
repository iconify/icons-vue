<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt8dwrb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yt8dwrb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:station-wagon-and-tag" /></template>
