<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9o8brmdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9o8brmdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:time-lapse-solid" /></template>
