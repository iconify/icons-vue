<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfk-bw21h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfk-bw21h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:text-align-right" /></template>
