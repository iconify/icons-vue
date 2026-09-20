<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e51u0kr-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e51u0kr-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-minus4-filled" /></template>
