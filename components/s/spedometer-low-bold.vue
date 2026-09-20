<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7bco-s1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d7bco-s1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:spedometer-low-bold" /></template>
