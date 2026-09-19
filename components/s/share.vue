<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us_d39b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="us_d39b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:share" /></template>
