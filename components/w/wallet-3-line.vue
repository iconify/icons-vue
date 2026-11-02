<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0drnmb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0drnmb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wallet-3-line" /></template>
