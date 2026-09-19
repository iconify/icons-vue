<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjchplbvr.css';
import '../../css/c/cbd476sji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zjchplbvr"/><path class="cbd476sji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:newspaper" /></template>
