<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9fh_quic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9fh_quic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:xing" /></template>
