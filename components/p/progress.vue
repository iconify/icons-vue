<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isq7whgdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isq7whgdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:progress" /></template>
