<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g59sbscng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g59sbscng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:socket-check" /></template>
