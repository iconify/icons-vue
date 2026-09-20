<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrvr5sfgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yrvr5sfgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minio-dark" /></template>
