<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebrfcd7vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebrfcd7vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer-cog-outline" /></template>
