<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doy8l7bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="doy8l7bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:rocket-solid" /></template>
