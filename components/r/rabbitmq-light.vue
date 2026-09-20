<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7l31kb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o7l31kb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rabbitmq-light" /></template>
