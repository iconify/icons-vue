<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3enxxbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z3enxxbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:multiuser-device" /></template>
