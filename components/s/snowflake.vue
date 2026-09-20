<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knxpz_b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="knxpz_b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:snowflake" /></template>
