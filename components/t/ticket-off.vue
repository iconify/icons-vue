<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-d1exbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-d1exbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ticket-off" /></template>
