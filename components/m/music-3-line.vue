<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k93xi3wmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k93xi3wmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:music-3-line" /></template>
