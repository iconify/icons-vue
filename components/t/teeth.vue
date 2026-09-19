<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxwa2fbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="jxwa2fbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:teeth" /></template>
