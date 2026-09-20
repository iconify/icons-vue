<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu35q8g9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yu35q8g9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:mobile-alt-solid" /></template>
