<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/una5hpbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="una5hpbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:pen-tool" /></template>
