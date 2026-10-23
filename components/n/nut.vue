<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c02ksmlsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c02ksmlsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:nut" /></template>
