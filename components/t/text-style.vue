<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm45gt85n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cm45gt85n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:text-style" /></template>
