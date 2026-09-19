<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnj4z1-0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nnj4z1-0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:volume-up-filled-alt" /></template>
