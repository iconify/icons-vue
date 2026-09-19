<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps5vdrchl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps5vdrchl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:monitor" /></template>
