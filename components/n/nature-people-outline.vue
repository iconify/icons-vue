<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9wgj2wmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9wgj2wmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:nature-people-outline" /></template>
