<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tshmz1hxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tshmz1hxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:shekel-sign" /></template>
