<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4-jhn-gz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="m4-jhn-gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-smashing-mag" /></template>
