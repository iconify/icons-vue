<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5h3u4r9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="t5h3u4r9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-transfer-only-stroke-12" /></template>
