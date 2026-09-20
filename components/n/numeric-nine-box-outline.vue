<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqr4w3gel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqr4w3gel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-nine-box-outline" /></template>
