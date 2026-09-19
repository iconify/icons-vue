<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cebocs6cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cebocs6cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:see-no-evil-monkey" /></template>
