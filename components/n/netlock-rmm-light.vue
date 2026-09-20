<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3aqtzbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t3aqtzbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netlock-rmm-light" /></template>
