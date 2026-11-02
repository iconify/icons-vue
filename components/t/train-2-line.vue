<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyzl2jfnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyzl2jfnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:train-2-line" /></template>
