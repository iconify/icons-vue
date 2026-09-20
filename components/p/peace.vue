<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hweq6sf4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hweq6sf4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:peace" /></template>
