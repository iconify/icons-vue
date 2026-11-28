<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9_4sgipx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9_4sgipx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:send-clock" /></template>
