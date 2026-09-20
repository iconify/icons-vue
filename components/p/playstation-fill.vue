<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srbhv8gzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srbhv8gzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:playstation-fill" /></template>
