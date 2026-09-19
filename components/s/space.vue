<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp0hb03lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp0hb03lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:space" /></template>
