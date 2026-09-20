<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8l0lnbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i8l0lnbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:text-square-solid" /></template>
