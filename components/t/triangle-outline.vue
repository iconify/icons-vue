<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c18e-5bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c18e-5bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:triangle-outline" /></template>
