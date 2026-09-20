<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmk0qacjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmk0qacjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:tab" /></template>
