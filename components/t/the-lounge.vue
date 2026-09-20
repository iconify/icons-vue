<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o84xpx01m.css';
import '../../css/u/ugibgdcyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o84xpx01m"/><path class="ugibgdcyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:the-lounge" /></template>
