<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srh2llbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="srh2llbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:server-filled" /></template>
