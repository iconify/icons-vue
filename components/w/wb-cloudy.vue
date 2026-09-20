<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je79ww9ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je79ww9ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wb-cloudy" /></template>
