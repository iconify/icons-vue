<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0zfj_7yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d0zfj_7yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:tablet-alt" /></template>
