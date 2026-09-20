<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jam089b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jam089b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:screen-curve-solid" /></template>
