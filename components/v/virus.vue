<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0kc1kbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w0kc1kbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:virus" /></template>
