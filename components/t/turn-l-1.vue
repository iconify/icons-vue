<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz2u_uuor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz2u_uuor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:turn-l-1" /></template>
