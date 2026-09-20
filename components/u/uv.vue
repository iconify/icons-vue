<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww-0lbb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":41,"height":41};
const content = `<path class="ww-0lbb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:uv" /></template>
