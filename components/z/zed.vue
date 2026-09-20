<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn7escblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cn7escblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zed" /></template>
