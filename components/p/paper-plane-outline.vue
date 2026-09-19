<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld3pukxpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld3pukxpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:paper-plane-outline" /></template>
