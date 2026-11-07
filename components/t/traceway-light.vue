<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr0rmvbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xr0rmvbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:traceway-light" /></template>
