<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpwh28blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpwh28blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:za-sort-descending-letters-line" /></template>
