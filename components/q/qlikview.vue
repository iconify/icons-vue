<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm2_ybbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xm2_ybbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:qlikview" /></template>
