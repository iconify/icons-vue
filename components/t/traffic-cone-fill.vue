<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpsx_fbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpsx_fbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:traffic-cone-fill" /></template>
