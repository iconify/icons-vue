<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szzlztz1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szzlztz1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:radar-2-line" /></template>
