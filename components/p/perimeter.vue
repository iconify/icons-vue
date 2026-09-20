<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkjqepqep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkjqepqep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:perimeter" /></template>
