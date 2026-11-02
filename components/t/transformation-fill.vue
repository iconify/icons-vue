<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1h7f4f6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1h7f4f6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transformation-fill" /></template>
