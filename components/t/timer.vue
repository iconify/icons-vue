<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5_1g1oqt.css';
import '../../css/i/inrili5tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5_1g1oqt"/><path class="inrili5tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:timer" /></template>
