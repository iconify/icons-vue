<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls8624bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls8624bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:webhook-solid" /></template>
