<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh7b57y_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh7b57y_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:siri-line" /></template>
