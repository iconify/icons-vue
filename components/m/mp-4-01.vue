<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1-o7nbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1-o7nbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mp-4-01" /></template>
