<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucy9gabxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ucy9gabxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:religious-muslim" /></template>
