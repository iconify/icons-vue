<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hoh5_ms0c.css';
import '../../css/h/h-jbhd6rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hoh5_ms0c"/><path class="h-jbhd6rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:reflect-left-bold" /></template>
