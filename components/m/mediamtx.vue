<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny8rlnbhx.css';
import '../../css/o/o684edcxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ny8rlnbhx"/><path class="o684edcxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mediamtx" /></template>
