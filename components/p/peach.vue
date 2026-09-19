<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx9i_ms2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gx9i_ms2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:peach" /></template>
