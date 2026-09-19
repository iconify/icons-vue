<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k37_r3b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="k37_r3b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:snow" /></template>
