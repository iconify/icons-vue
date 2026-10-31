<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox_vk2bqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox_vk2bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-horizontal-bulk-round" /></template>
