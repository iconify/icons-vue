<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erzf03bmv.css';
import '../../css/i/iwbjh1dmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="erzf03bmv"/><path class="iwbjh1dmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:united-airlines" /></template>
