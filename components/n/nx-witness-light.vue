<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iudnm730z.css';
import '../../css/l/lwo5f24pv.css';
import '../../css/l/ln0ym_was.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iudnm730z"/><path class="lwo5f24pv"/><path class="ln0ym_was"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nx-witness-light" /></template>
