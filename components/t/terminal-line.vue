<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcbv_q0xa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcbv_q0xa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:terminal-line" /></template>
