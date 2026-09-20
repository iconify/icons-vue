<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izg9xkbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izg9xkbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mlb" /></template>
