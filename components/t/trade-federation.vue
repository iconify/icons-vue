<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmw063b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gmw063b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:trade-federation" /></template>
