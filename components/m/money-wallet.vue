<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce3c8rxfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ce3c8rxfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:money-wallet" /></template>
