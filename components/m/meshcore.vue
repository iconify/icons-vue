<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xni24ebau.css';
import '../../css/e/emg8bu5vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xni24ebau"/><path class="emg8bu5vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:meshcore" /></template>
