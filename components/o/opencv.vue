<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxz6et8is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxz6et8is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:opencv" /></template>
