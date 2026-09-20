<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn6vp_b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn6vp_b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:twenty" /></template>
