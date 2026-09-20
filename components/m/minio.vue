<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozigqchsx.css';
import '../../css/u/u4tpbbpvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ozigqchsx"/><path class="u4tpbbpvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minio" /></template>
