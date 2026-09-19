<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epnbenbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="epnbenbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:options" /></template>
