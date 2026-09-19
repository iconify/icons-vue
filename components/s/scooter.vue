<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz0ugac9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz0ugac9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:scooter" /></template>
