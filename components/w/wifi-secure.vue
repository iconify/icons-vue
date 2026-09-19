<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3vyg8drj.css';
import '../../css/l/ljcvjmvwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o3vyg8drj"/><path class="ljcvjmvwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:wifi-secure" /></template>
