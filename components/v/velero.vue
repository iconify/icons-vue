<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msn8vpxnr.css';
import '../../css/o/oj8vp5bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="msn8vpxnr"/><path class="oj8vp5bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:velero" /></template>
