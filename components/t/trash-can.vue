<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ary9esnqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ary9esnqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:trash-can" /></template>
