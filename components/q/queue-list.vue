<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru1h04b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru1h04b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:queue-list" /></template>
