<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt807ulwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt807ulwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pedastal-fan-hollow" /></template>
