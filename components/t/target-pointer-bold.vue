<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkhkx8d9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="pkhkx8d9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:target-pointer-bold" /></template>
