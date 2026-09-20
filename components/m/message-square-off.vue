<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x90phvbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x90phvbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:message-square-off" /></template>
