<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr_nnrqul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yr_nnrqul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:play-outline" /></template>
