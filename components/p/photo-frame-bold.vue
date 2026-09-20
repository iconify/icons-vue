<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpnkdflmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpnkdflmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:photo-frame-bold" /></template>
