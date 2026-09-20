<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yml45ibji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yml45ibji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:server-remove" /></template>
