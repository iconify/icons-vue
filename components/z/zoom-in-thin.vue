<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn83ztbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn83ztbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:zoom-in-thin" /></template>
