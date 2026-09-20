<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw_djzbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bw_djzbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:vuejs" /></template>
