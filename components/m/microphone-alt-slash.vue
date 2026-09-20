<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-2chxb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f-2chxb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:microphone-alt-slash" /></template>
