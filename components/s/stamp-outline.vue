<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru0kn4bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ru0kn4bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:stamp-outline" /></template>
