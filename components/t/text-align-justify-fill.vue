<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4dzq_bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4dzq_bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-align-justify-fill" /></template>
