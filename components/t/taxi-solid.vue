<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgn0bs1rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lgn0bs1rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:taxi-solid" /></template>
