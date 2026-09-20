<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km4-ce44e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km4-ce44e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:minus-box-multiple" /></template>
