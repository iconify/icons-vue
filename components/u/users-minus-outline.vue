<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bag5a7bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bag5a7bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:users-minus-outline" /></template>
