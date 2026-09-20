<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-m9inbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d-m9inbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:pet-animals-bear" /></template>
