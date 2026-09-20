<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imkf5vvcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="imkf5vvcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:teddycloud-light" /></template>
