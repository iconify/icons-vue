<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z54yactek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z54yactek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:office-chair" /></template>
