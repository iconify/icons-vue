<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgf5td-lq.css';
import '../../css/m/mpdgb_2fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgf5td-lq"/><path class="mpdgb_2fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-arrow-up-exit-filled" /></template>
