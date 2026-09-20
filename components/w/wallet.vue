<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfimg1yuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfimg1yuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wallet" /></template>
