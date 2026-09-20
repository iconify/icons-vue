<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwl48ebgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uwl48ebgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:subtraction" /></template>
