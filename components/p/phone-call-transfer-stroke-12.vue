<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kald8wfhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kald8wfhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-transfer-stroke-12" /></template>
