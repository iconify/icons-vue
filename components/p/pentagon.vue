<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe2zeeb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe2zeeb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pentagon" /></template>
