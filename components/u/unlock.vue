<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi64b0bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":560,"height":840};
const content = `<path class="yi64b0bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:unlock" /></template>
