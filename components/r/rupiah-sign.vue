<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgeuypctf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lgeuypctf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:rupiah-sign" /></template>
