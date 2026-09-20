<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo5xuvb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo5xuvb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:user" /></template>
