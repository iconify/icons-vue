<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t90i62flf.css';
import '../../css/r/re_renben.css';
import '../../css/a/aw5f0f-8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t90i62flf"/><path class="re_renben"/><path class="aw5f0f-8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:paypal" /></template>
