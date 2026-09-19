<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4bk81bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m4bk81bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:z-systems" /></template>
