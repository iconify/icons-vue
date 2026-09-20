<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flw272beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flw272beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:seal" /></template>
