<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1i-fu7vn.css';
import '../../css/y/y5w19acgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e1i-fu7vn"/><path class="y5w19acgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-completion-suggester" /></template>
