<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtdwdp3he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtdwdp3he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:suitcase-line" /></template>
