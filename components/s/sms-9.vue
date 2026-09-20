<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_k0w1bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s_k0w1bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:sms-9" /></template>
