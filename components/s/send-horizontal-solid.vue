<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwk_-hbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwk_-hbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:send-horizontal-solid" /></template>
