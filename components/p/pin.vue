<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktcsf7b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktcsf7b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:pin" /></template>
