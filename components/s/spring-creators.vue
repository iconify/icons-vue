<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uela_vuco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uela_vuco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:spring-creators" /></template>
