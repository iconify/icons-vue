<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtus33btr.css';
import '../../css/z/zeit0ibdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="qtus33btr"/><path class="zeit0ibdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pinepods" /></template>
