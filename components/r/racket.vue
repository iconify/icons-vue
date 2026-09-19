<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv2_abjze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bv2_abjze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:racket" /></template>
