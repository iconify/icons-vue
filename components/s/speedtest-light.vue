<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyuqmdb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xyuqmdb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:speedtest-light" /></template>
