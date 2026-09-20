<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgl9-i0zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lgl9-i0zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:search" /></template>
