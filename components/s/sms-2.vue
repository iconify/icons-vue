<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkvs6705i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tkvs6705i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:sms-2" /></template>
