<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3somibqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c3somibqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:smoking-ban-solid" /></template>
