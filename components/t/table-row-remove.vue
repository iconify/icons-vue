<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmpeqjlep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmpeqjlep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-row-remove" /></template>
