<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inl2l1b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="inl2l1b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:send-solid" /></template>
