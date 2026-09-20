<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm3w5dbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm3w5dbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:oppo" /></template>
