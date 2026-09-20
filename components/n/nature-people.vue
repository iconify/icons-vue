<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npiauk8yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npiauk8yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:nature-people" /></template>
