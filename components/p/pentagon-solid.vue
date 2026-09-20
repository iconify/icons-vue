<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiwobry8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xiwobry8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pentagon-solid" /></template>
