<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u52z9_ngd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u52z9_ngd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:stock-solid" /></template>
