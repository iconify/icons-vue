<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhnn1_t4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yhnn1_t4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:recyclarr-light" /></template>
