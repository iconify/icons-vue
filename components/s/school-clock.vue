<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-8v1_b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-8v1_b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:school-clock" /></template>
