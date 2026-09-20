<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysuq3zb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ysuq3zb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:sms-3" /></template>
