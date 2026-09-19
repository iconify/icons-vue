<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwrz3wh0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fwrz3wh0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:scale-sharp" /></template>
