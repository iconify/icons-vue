<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvw4ydbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvw4ydbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:status-filled" /></template>
