<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuk76lbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuk76lbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tornado-fill" /></template>
