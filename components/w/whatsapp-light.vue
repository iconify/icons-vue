<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fon-ibcks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fon-ibcks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:whatsapp-light" /></template>
