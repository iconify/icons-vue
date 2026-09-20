<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyvdw92my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tyvdw92my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:move-right-solid" /></template>
