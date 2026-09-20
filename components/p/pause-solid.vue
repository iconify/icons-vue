<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk6t47z6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yk6t47z6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:pause-solid" /></template>
