<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfmit8bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pfmit8bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:shopping-help-information" /></template>
