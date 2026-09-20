<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sftsmcbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sftsmcbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sector-line" /></template>
