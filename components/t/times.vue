<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnksxrbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1216,"height":1312};
const content = `<path class="lnksxrbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:times" /></template>
