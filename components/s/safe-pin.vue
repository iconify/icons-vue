<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or11ckbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="or11ckbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:safe-pin" /></template>
