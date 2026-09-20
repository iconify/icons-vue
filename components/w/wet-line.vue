<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfy4_i41q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfy4_i41q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wet-line" /></template>
