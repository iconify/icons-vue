<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm6fy4buw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm6fy4buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:menu" /></template>
