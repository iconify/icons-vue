<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg2irbcwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg2irbcwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-10-fill" /></template>
