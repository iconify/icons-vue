<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrdvcwidb.css';
import '../../css/w/wyg5aebcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrdvcwidb"/><path class="wyg5aebcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-up-bold-duotone" /></template>
