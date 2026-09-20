<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5ovz_bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5ovz_bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square-chevron-up-sharp" /></template>
