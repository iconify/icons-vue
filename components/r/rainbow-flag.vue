<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdynctb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="rdynctb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:rainbow-flag" /></template>
