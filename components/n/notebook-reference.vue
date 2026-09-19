<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lswr9wrdr.css';
import '../../css/u/unos9unxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lswr9wrdr"/><path class="unos9unxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:notebook-reference" /></template>
