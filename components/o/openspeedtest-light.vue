<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6b9k4bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f6b9k4bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openspeedtest-light" /></template>
