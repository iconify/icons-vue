<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8v73blpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8v73blpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:truck-outline" /></template>
