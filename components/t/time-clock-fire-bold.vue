<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsf-qnbqy.css';
import '../../css/b/b19x8pyha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsf-qnbqy"/><path class="b19x8pyha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:time-clock-fire-bold" /></template>
