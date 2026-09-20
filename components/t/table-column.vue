<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci7jiqysf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci7jiqysf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-column" /></template>
