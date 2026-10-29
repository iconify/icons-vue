<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg_u_wy3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg_u_wy3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:panel-bottom-solid" /></template>
