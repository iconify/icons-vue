<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8k2tzb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j8k2tzb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:persons-lock" /></template>
