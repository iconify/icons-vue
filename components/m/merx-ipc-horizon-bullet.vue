<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljz9_d-pg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljz9_d-pg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:merx-ipc-horizon-bullet" /></template>
