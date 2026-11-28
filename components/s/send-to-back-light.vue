<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms497sa8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ms497sa8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:send-to-back-light" /></template>
