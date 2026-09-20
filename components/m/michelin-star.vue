<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eelbogbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eelbogbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:michelin-star" /></template>
