<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaygjqbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="zaygjqbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:sign-road-2" /></template>
