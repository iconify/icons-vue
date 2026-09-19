<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g503shx1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g503shx1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:tablets-1" /></template>
