<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liqt4ecgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="liqt4ecgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pills2-filled" /></template>
