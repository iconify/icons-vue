<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alg-2d_nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="alg-2d_nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:triangle-circle-16" /></template>
