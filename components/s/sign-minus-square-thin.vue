<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etw8_08xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etw8_08xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-minus-square-thin" /></template>
