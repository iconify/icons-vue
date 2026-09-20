<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csol4q46k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csol4q46k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:page-break" /></template>
