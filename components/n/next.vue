<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxdr3cc4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":224,"height":472};
const content = `<path class="cxdr3cc4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:next" /></template>
