<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh6ex02dp.css';
import '../../css/o/opkm_bb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mh6ex02dp"/><path class="opkm_bb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:mic-outline" /></template>
