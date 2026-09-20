<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq5bo2w_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mq5bo2w_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tillywork-light" /></template>
