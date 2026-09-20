<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsba6-s3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dsba6-s3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zorin-os-light" /></template>
