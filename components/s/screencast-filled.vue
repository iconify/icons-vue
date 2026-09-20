<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkxrg8bqx.css';
import '../../css/v/vcwbpi0dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkxrg8bqx"/><path class="vcwbpi0dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:screencast-filled" /></template>
