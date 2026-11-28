<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoawi1bfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoawi1bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:upload" /></template>
