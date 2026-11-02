<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlm2j4byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlm2j4byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:reddit-fill" /></template>
