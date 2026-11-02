<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaj_3nngg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaj_3nngg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:merge-fill" /></template>
