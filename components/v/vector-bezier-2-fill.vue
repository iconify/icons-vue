<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy0li2w-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy0li2w-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vector-bezier-2-fill" /></template>
