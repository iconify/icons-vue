<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qphgtx_0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qphgtx_0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:scuba-mask-off" /></template>
