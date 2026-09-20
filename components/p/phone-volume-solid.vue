<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v90v0zbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v90v0zbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:phone-volume-solid" /></template>
