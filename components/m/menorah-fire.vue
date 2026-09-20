<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpcjweb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpcjweb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:menorah-fire" /></template>
