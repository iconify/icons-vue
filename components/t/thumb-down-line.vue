<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6o_xnbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6o_xnbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:thumb-down-line" /></template>
