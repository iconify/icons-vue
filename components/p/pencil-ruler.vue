<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz6ptgzuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz6ptgzuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:pencil-ruler" /></template>
