<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy6nseels.css';
import '../../css/q/qbt4lgb4f.css';
import '../../css/i/i5jz4wyel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vy6nseels"/><path class="qbt4lgb4f"/><path class="i5jz4wyel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:senlo" /></template>
