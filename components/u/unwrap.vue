<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh6h5phkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hh6h5phkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:unwrap" /></template>
