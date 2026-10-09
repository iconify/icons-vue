<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc4zo-bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uc4zo-bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paperclip-20" /></template>
