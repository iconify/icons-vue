<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqy8xebjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqy8xebjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rcn" /></template>
