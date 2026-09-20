<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts8p5pbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts8p5pbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:north-east-escape-line" /></template>
