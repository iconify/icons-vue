<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-g782bfv.css';
import '../../css/z/z8g5xoj5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f-g782bfv"/><path class="z8g5xoj5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:mail-unread" /></template>
