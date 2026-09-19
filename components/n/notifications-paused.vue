<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzyz4ebqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":432};
const content = `<path class="vzyz4ebqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:notifications-paused" /></template>
