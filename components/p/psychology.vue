<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktxbgbbpn.css';
import '../../css/g/g_4d4-bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktxbgbbpn"/><path class="g_4d4-bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:psychology" /></template>
