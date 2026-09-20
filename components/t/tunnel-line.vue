<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olip4ntqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olip4ntqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tunnel-line" /></template>
