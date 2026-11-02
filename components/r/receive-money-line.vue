<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2x3-6xto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2x3-6xto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:receive-money-line" /></template>
