<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa85hmxqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xa85hmxqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:print-outline" /></template>
