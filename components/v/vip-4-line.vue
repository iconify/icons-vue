<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjx98-60m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjx98-60m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vip-4-line" /></template>
