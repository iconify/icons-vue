<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eli8gablv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eli8gablv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:seed-add" /></template>
