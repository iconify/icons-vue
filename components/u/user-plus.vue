<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs4ul0b6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs4ul0b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-plus" /></template>
