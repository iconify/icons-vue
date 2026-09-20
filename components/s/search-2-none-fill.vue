<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8aj_0y_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8aj_0y_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:search-2-none-fill" /></template>
