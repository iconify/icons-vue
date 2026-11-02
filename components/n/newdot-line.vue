<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_6tq2bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_6tq2bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:newdot-line" /></template>
