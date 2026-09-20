<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imr4gyvdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="imr4gyvdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:projector-outline" /></template>
