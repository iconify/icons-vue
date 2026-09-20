<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d59vkeb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1001,"height":667};
const content = `<path class="d59vkeb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tidal-light" /></template>
