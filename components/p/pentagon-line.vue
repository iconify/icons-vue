<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp4kg59fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp4kg59fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pentagon-line" /></template>
