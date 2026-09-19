<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leg0v_b6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="leg0v_b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:softball" /></template>
