<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i97yjjbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i97yjjbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:package-node" /></template>
