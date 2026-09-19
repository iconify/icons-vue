<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9gf-lmhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="w9gf-lmhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-grid-1x2-fill" /></template>
