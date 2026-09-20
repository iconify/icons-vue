<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj8vw15bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fj8vw15bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:registered" /></template>
