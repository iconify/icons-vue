<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq1ek_buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq1ek_buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-pi-solid" /></template>
