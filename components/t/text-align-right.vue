<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owp06vahj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owp06vahj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:text-align-right" /></template>
