<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctweey_bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ctweey_bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:pig" /></template>
