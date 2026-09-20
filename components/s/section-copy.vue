<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf4gkg6yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf4gkg6yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:section-copy" /></template>
