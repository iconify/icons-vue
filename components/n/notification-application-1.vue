<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6lsl9b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="u6lsl9b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:notification-application-1" /></template>
