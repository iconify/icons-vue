<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs_m5qbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs_m5qbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:time" /></template>
