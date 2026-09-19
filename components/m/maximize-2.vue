<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_ju5sbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_ju5sbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:maximize-2" /></template>
