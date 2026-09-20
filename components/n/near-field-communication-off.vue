<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ponf9zbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ponf9zbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:near-field-communication-off" /></template>
