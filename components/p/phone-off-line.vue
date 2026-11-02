<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uodvst3vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uodvst3vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:phone-off-line" /></template>
