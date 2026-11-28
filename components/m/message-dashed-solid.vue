<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snn96nbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snn96nbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-dashed-solid" /></template>
