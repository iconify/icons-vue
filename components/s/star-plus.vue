<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9f8idtsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9f8idtsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:star-plus" /></template>
