<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spwm54azc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spwm54azc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:yuanbao-line" /></template>
