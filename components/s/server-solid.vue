<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj9bm4bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cj9bm4bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:server-solid" /></template>
