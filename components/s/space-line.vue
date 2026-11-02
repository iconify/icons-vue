<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x14tm3bdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x14tm3bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:space-line" /></template>
