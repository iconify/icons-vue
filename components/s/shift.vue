<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plii2cbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="plii2cbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:shift" /></template>
