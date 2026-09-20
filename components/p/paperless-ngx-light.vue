<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbb4g5h2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zbb4g5h2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:paperless-ngx-light" /></template>
