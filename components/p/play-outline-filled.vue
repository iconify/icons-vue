<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzwc1y54b.css';
import '../../css/r/ra66rbckd.css';
import '../../css/z/zgszk2b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bzwc1y54b"/><path class="ra66rbckd"/><path class="zgszk2b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:play-outline-filled" /></template>
