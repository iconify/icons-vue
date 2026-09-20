<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni_0eabwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ni_0eabwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:user-tie-solid" /></template>
