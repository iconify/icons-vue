<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aux2x-bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="aux2x-bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shell" /></template>
