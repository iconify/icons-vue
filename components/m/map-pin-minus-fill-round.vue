<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8trf56cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8trf56cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-minus-fill-round" /></template>
