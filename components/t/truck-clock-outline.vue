<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-jdclmww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-jdclmww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:truck-clock-outline" /></template>
