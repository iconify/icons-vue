<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-zwmjkxi.css';
import '../../css/w/w6h-t2a-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b f-zwmjkxi"/><path class="b w6h-t2a-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:web-components" /></template>
