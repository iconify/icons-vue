<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxqo9ccey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fxqo9ccey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:pencil-alt-solid" /></template>
