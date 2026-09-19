<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhf4zz28w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rhf4zz28w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-list-box" /></template>
