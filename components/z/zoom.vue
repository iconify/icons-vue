<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ladfd1b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ladfd1b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:zoom" /></template>
