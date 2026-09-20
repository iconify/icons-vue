<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue-hx7a2u.css';
import '../../css/r/r97zvfb6s.css';
import '../../css/c/c18_ysapx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ue-hx7a2u"/><path class="r97zvfb6s"/><path class="c18_ysapx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:taiga-dark" /></template>
