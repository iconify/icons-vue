<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzp15iw1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzp15iw1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:virus-line" /></template>
