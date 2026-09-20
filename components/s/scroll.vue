<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_7x--shm.css';
import '../../css/l/luq2o7biq.css';
import '../../css/l/l13e8s3zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_7x--shm"/><path class="luq2o7biq"/><path class="l13e8s3zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:scroll" /></template>
