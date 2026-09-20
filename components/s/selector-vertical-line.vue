<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi0nwc0pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi0nwc0pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:selector-vertical-line" /></template>
