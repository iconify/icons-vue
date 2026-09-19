<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk_dfeb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="bk_dfeb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:scooter-outline" /></template>
