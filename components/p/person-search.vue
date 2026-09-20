<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrz9yob5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrz9yob5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:person-search" /></template>
