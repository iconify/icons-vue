<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ask_q2bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ask_q2bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:rotate-90-right" /></template>
