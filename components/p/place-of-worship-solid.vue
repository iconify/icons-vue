<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee4dfac4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ee4dfac4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:place-of-worship-solid" /></template>
