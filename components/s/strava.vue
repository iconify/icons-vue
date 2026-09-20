<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnyallb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rnyallb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:strava" /></template>
