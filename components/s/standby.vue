<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivguv72lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ivguv72lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:standby" /></template>
