<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2c8fsbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t2c8fsbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:ship" /></template>
