<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u20j3na4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u20j3na4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:tab-slash" /></template>
