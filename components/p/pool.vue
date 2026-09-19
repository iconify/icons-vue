<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npbkbobuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="npbkbobuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:pool" /></template>
