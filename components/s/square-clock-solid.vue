<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7gkr3nsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d7gkr3nsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:square-clock-solid" /></template>
