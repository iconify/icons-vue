<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v936ribwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v936ribwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pool-ladder-solid" /></template>
