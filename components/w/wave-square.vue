<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umps4yb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="umps4yb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:wave-square" /></template>
