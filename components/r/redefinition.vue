<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkex5867a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bkex5867a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:redefinition" /></template>
