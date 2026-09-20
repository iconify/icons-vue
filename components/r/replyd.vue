<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1_lhm1wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u1_lhm1wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:replyd" /></template>
