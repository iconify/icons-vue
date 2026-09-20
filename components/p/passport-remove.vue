<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv8qo5c_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv8qo5c_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:passport-remove" /></template>
