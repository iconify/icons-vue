<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzow2z1zo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hzow2z1zo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:meh-blank" /></template>
