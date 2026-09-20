<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8-suub8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h8-suub8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:plus-square" /></template>
