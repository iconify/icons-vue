<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz0tcpzbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz0tcpzbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:voelkner" /></template>
