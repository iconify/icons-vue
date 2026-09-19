<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kekhe7bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kekhe7bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:save" /></template>
