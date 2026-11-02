<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfyx4o23a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfyx4o23a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:playground-line" /></template>
