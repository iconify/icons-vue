<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxhzv1nnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lxhzv1nnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:plane" /></template>
