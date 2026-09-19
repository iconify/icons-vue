<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqp_m4bni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kqp_m4bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:vine" /></template>
