<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu_kr_k0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="uu_kr_k0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:resolving" /></template>
