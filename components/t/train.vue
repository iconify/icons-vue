<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za8lh3llf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="za8lh3llf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:train" /></template>
