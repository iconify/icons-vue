<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boqllab4b.css';
import '../../css/a/am0b34b6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="boqllab4b"/><path class="am0b34b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:warning-square" /></template>
