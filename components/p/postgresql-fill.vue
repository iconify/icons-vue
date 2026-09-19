<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t99tz67ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t99tz67ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:postgresql-fill" /></template>
