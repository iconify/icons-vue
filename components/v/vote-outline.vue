<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb9su6z-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb9su6z-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vote-outline" /></template>
