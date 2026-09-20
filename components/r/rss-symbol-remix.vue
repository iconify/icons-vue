<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekj4x2bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ekj4x2bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:rss-symbol-remix" /></template>
