<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf33qeb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf33qeb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:minimize-solid" /></template>
