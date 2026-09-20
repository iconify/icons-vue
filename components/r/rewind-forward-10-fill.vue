<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq_hv3bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq_hv3bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-10-fill" /></template>
