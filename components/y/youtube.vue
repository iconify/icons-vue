<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1h_w7bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f1h_w7bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:youtube" /></template>
