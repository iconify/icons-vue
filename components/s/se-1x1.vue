<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwq_awb_v.css';
import '../../css/i/isfqmkfad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uwq_awb_v"/><path class="isfqmkfad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:se-1x1" /></template>
