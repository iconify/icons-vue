<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouae2vbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ouae2vbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pencil-solid" /></template>
