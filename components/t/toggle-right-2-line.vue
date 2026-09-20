<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h29abmbpa.css';
import '../../css/i/iu_8x_b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h29abmbpa"/><path class="iu_8x_b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toggle-right-2-line" /></template>
