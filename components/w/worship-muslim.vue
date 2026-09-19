<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh36b_exl.css';
import '../../css/t/t2wztiban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bh36b_exl"/><path class="t2wztiban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:worship-muslim" /></template>
