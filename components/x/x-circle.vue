<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpv2s9b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpv2s9b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:x-circle" /></template>
