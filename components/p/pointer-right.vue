<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjqfn-boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kjqfn-boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pointer-right" /></template>
