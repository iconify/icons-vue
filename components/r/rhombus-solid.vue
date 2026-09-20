<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dez_3qb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dez_3qb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rhombus-solid" /></template>
