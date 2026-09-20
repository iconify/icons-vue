<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq6o0ew3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq6o0ew3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:pyramid-solid" /></template>
