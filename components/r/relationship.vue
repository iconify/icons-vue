<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujvh15bzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ujvh15bzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:relationship" /></template>
