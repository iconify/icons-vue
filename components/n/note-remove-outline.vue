<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5t-a2b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5t-a2b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:note-remove-outline" /></template>
