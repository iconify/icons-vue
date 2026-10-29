<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fue8pumlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fue8pumlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:smartphone-solid" /></template>
