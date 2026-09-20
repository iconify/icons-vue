<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0t8zkbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u0t8zkbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sad-face-in-circle" /></template>
