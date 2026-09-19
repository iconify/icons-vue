<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdve-zb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdve-zb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:minimize-02" /></template>
