<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-wzpbwcp.css';
import '../../css/c/cgsdd0bmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-wzpbwcp"/><path clip-rule="evenodd" class="cgsdd0bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paper-bin-bold-duotone" /></template>
