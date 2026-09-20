<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7bmpyxez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7bmpyxez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pokt" /></template>
