<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzty5h1lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzty5h1lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sunglasses" /></template>
