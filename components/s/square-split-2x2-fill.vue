<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz19t2nyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="nz19t2nyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-split-2x2-fill" /></template>
