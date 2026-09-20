<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt-ms-9kv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rt-ms-9kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:mizuni" /></template>
