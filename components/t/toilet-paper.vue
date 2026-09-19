<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9b2swbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="q9b2swbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:toilet-paper" /></template>
