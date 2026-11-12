<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqfdm7snc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sqfdm7snc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minio-light" /></template>
