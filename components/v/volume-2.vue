<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7lj2v1ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7lj2v1ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:volume-2" /></template>
