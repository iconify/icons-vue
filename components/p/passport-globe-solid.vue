<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3a2ybb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q3a2ybb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:passport-globe-solid" /></template>
