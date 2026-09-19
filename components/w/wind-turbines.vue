<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fck1plbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="fck1plbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:wind-turbines" /></template>
