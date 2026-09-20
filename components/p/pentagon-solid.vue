<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfo6bsb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wfo6bsb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pentagon-solid" /></template>
