<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe550s3qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe550s3qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:shuffle" /></template>
