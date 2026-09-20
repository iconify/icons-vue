<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxti2cc2i.css';
import '../../css/j/j3c-dicsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qxti2cc2i"/><path class="j3c-dicsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netlock-rmm" /></template>
