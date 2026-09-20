<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zebtg939x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zebtg939x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:pen-fancy-solid" /></template>
