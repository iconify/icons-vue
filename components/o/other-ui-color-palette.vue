<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf4dhebff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cf4dhebff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-color-palette" /></template>
