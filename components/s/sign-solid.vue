<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_fea6bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g_fea6bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sign-solid" /></template>
