<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euxmq9mxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="euxmq9mxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:rewind-filled" /></template>
