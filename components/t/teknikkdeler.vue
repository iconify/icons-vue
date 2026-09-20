<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yevpafbzb.css';
import '../../css/t/tzflgcclh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yevpafbzb"/><path class="tzflgcclh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:teknikkdeler" /></template>
