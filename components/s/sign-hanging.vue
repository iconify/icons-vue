<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwbn2m-gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vwbn2m-gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:sign-hanging" /></template>
