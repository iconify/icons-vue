<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecsf4pbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecsf4pbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:monitor-minus-solid" /></template>
