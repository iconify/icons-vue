<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ring6vbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ring6vbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:settings-solid" /></template>
