<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-eh1fc1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-eh1fc1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:users-question" /></template>
