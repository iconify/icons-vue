<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb5ck8ldz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lb5ck8ldz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ong" /></template>
