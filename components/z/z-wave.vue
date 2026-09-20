<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h15weabey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h15weabey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:z-wave" /></template>
