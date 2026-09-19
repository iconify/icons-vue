<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g34r42blo.css';
import '../../css/c/czru7nb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g34r42blo"/><path class="czru7nb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sync-settings" /></template>
