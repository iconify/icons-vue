<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv5k-0bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vv5k-0bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:whisper-money-light" /></template>
