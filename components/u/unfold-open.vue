<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af13y3bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="af13y3bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:unfold-open" /></template>
