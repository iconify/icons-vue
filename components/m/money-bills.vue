<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzfha4bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bzfha4bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:money-bills" /></template>
