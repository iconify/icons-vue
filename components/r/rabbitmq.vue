<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnwp0xbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wnwp0xbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rabbitmq" /></template>
