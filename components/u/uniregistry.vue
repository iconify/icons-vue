<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv1zq6sks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zv1zq6sks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:uniregistry" /></template>
