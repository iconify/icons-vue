<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl-ijsbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hl-ijsbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:server-off" /></template>
