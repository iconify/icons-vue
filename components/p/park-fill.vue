<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlf0m3-1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlf0m3-1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:park-fill" /></template>
