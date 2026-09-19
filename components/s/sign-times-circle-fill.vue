<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifi4wh1fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ifi4wh1fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-times-circle-fill" /></template>
