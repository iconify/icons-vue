<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzxml0eis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="nzxml0eis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:voicemail" /></template>
