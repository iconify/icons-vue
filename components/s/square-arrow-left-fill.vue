<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/outf-5w6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="outf-5w6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:square-arrow-left-fill" /></template>
