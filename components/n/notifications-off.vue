<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opo2qwbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="opo2qwbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:notifications-off" /></template>
