<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2f32u7hy.css';
import '../../css/p/pfssstxrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="r2f32u7hy"/><path class="pfssstxrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:mobile-phone" /></template>
