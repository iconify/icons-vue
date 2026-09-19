<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/civmh-b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="civmh-b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:newspaper" /></template>
