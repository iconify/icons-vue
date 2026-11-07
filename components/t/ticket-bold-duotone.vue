<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3oem8bbx.css';
import '../../css/x/x_l41xukd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i3oem8bbx"/><path class="x_l41xukd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ticket-bold-duotone" /></template>
