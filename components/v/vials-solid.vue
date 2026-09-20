<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4w_49bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i4w_49bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:vials-solid" /></template>
