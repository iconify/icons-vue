<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow83bgbqz.css';
import '../../css/v/vg49bdvkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ow83bgbqz"/><path class="vg49bdvkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-close-circle-outline" /></template>
