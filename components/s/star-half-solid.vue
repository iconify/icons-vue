<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdeyaq8zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xdeyaq8zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:star-half-solid" /></template>
