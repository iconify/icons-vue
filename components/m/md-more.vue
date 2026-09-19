<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwt5gdbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zwt5gdbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-more" /></template>
