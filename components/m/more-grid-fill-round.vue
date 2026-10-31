<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_m8swbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_m8swbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-grid-fill-round" /></template>
