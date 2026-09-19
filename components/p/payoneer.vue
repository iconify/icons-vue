<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4te6mbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="q4te6mbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:payoneer" /></template>
