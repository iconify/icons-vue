<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lknh6wbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lknh6wbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stop" /></template>
