<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-7r6lf6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-7r6lf6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer-edit-outline" /></template>
