<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgdyellrq.css';
import '../../css/s/slqdrx-ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgdyellrq"/><path class="slqdrx-ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sleeping-bold" /></template>
