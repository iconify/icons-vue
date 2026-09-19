<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf8zvibwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="pf8zvibwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:vr-cardboard" /></template>
