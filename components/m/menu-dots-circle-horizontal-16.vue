<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es71m-npu.css';
import '../../css/v/vx5rr602v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="es71m-npu"/><path class="vx5rr602v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:menu-dots-circle-horizontal-16" /></template>
