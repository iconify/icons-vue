<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd42r404p.css';
import '../../css/k/kigsbgfya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cd42r404p"/><path class="kigsbgfya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:misuse-alt" /></template>
