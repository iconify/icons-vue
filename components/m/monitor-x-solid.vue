<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avc904bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avc904bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:monitor-x-solid" /></template>
