<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxqy_1fvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxqy_1fvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:thermometer-fill" /></template>
