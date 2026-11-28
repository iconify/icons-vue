<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/matp353vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="matp353vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:math-symbols-solid" /></template>
