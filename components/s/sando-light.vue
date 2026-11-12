<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo7956bee.css';
import '../../css/a/asu1pqv5y.css';
import '../../css/n/n2cwm3b-l.css';
import '../../css/y/yw1-5cc1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mo7956bee"/><path class="asu1pqv5y"/><path class="n2cwm3b-l"/><path class="yw1-5cc1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sando-light" /></template>
