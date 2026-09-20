<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbh9tiw4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hbh9tiw4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:text-alginment-justified" /></template>
