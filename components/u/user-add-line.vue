<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svs_3lbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svs_3lbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-add-line" /></template>
