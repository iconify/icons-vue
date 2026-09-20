<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n73j_hptb.css';
import '../../css/t/tvrvbjbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n73j_hptb"/><path class="tvrvbjbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermc-paper" /></template>
