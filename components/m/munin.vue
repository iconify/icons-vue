<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ked3dlbrv.css';
import '../../css/q/qpoa4dbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ked3dlbrv"/><path class="qpoa4dbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:munin" /></template>
