<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayz3-lg7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ayz3-lg7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:telescope-solid" /></template>
