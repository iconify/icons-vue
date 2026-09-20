<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm3rfcb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wm3rfcb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:observation-tower" /></template>
