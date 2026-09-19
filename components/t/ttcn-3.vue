<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8mvcmb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":512};
const content = `<path class="c8mvcmb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ttcn-3" /></template>
