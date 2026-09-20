<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hadh28nsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hadh28nsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:people-carry" /></template>
