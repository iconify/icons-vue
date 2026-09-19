<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcq5-ib4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kcq5-ib4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:ship" /></template>
