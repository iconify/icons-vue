<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq9h4pbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aq9h4pbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:send-outline" /></template>
