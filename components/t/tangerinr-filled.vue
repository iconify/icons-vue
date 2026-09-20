<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgxdswbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgxdswbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tangerinr-filled" /></template>
