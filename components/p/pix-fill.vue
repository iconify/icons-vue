<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkxsbabrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkxsbabrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pix-fill" /></template>
