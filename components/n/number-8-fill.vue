<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv1kergsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sv1kergsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-8-fill" /></template>
