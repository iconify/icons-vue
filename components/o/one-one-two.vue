<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esbhv0bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="esbhv0bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:one-one-two" /></template>
