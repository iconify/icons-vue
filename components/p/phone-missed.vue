<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3dqssb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3dqssb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:phone-missed" /></template>
