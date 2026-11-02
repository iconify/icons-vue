<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shatulg1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shatulg1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rows-2-line" /></template>
