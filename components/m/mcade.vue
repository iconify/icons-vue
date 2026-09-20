<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6s6452ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6s6452ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mcade" /></template>
