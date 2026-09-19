<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqc_2glev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqc_2glev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:server-outline" /></template>
