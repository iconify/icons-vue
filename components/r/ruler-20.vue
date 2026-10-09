<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6etv2b0x.css';
import '../../css/q/qy70odgzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v6etv2b0x"/><path class="qy70odgzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ruler-20" /></template>
