<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnmc9_k6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="rnmc9_k6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squareeight" /></template>
