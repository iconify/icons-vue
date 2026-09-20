<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca9dfeugk.css';
import '../../css/r/rg1a49h5j.css';
import '../../css/s/scvi-omos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca9dfeugk"/><path class="rg1a49h5j"/><path class="scvi-omos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ubiq" /></template>
