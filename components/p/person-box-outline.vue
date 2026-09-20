<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz7ar6_-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz7ar6_-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:person-box-outline" /></template>
