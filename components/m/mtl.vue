<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzi6e6b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzi6e6b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mtl" /></template>
