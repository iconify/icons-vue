<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h43-4kifw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h43-4kifw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:spinner-2-sacle" /></template>
