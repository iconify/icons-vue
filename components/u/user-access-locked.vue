<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skc3wybvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="skc3wybvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-access-locked" /></template>
