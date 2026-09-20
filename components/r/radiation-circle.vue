<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb47ls34d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb47ls34d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:radiation-circle" /></template>
