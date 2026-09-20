<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8oh0_brq.css';
import '../../css/z/zb1p0hbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x8oh0_brq"/><path class="zb1p0hbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:orange-isp" /></template>
