<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aloutc9xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aloutc9xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:manufacturing" /></template>
