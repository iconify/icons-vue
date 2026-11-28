<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aozbnhbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aozbnhbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:strawberry-heart" /></template>
