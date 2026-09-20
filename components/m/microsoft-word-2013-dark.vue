<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlg3a0b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wlg3a0b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-word-2013-dark" /></template>
