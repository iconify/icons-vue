<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsz_46bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsz_46bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:process-line" /></template>
