<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr6-gac2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr6-gac2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:omega-line" /></template>
