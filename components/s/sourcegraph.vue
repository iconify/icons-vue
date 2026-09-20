<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj6o8abyb.css';
import '../../css/b/bnus8tbil.css';
import '../../css/t/t3kxshl8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":262,"height":262,"left":-3};
const content = `<path class="lj6o8abyb"/><path class="bnus8tbil"/><path class="t3kxshl8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sourcegraph" /></template>
