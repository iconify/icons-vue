<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o43zpgbqc.css';
import '../../css/w/w5cu6gb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o43zpgbqc"/><path class="w5cu6gb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:receipt" /></template>
