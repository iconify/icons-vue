<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8ilg030l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8ilg030l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:minimize-gloss" /></template>
