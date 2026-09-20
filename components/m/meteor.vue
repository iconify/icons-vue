<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h18uyabnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h18uyabnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:meteor" /></template>
