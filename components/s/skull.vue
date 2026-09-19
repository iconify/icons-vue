<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnue5lbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnue5lbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:skull" /></template>
