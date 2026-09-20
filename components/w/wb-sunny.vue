<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaa6obcen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jaa6obcen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wb-sunny" /></template>
