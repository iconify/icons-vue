<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwivgrbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cwivgrbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minio-dark" /></template>
