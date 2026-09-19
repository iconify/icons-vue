<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piz04983m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="piz04983m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:twitter" /></template>
