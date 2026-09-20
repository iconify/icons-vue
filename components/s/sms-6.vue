<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhehwf5ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lhehwf5ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:sms-6" /></template>
