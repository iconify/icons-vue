<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe5zgaboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe5zgaboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:quote-right-line" /></template>
