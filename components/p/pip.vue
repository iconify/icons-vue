<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_rmvvcdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_rmvvcdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pip" /></template>
