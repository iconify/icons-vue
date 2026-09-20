<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw6_6gx7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jw6_6gx7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:thermometer-half-solid" /></template>
