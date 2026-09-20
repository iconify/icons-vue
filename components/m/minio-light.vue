<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpb3pvb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wpb3pvb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minio-light" /></template>
