<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i10f3sn0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i10f3sn0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:news" /></template>
