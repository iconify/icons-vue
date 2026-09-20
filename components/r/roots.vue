<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx5isab4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx5isab4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:roots" /></template>
