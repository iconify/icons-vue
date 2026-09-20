<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la2deubsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la2deubsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:scipy" /></template>
