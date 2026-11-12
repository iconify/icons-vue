<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn1fsybwx.css';
import '../../css/u/u4tpbbpvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vn1fsybwx"/><path class="u4tpbbpvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minio" /></template>
