<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r00c-ld7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r00c-ld7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:star-topper-line" /></template>
