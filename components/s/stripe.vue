<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhz5ljcbr.css';
import '../../css/w/wees9lb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hhz5ljcbr"/><path class="wees9lb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stripe" /></template>
