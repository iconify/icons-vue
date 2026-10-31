<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp0oxifbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp0oxifbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:send-gloss" /></template>
