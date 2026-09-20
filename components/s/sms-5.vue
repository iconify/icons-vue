<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvfwd6dby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kvfwd6dby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:sms-5" /></template>
