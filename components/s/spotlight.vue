<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh87u9zyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh87u9zyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:spotlight" /></template>
