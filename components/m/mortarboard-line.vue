<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj1rrox4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj1rrox4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mortarboard-line" /></template>
