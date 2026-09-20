<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj8l4qwvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj8l4qwvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timeline-remove" /></template>
