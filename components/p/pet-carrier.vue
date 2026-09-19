<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk2ph2lxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="dk2ph2lxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:pet-carrier" /></template>
