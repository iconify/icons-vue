<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8ly-hb2i.css';
import '../../css/e/enc01mbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q8ly-hb2i"/><path class="enc01mbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:subarr" /></template>
