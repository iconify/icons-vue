<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w58qsbbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w58qsbbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-check" /></template>
