<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4ncvtbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f4ncvtbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wrap-left-fill-16" /></template>
