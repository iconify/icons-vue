<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f998_qbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f998_qbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:school-xmark-outline" /></template>
