<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyd8d0txh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyd8d0txh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pool-disolved" /></template>
