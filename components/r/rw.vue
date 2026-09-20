<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp4mm0b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dp4mm0b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:rw" /></template>
