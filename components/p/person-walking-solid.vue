<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amo1dubnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amo1dubnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:person-walking-solid" /></template>
