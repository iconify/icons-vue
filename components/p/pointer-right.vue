<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4h4vibbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l4h4vibbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:pointer-right" /></template>
