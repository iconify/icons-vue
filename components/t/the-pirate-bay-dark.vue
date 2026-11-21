<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiemq2b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tiemq2b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:the-pirate-bay-dark" /></template>
