<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u35k7d0yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="u35k7d0yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:user-circle-star-bold" /></template>
