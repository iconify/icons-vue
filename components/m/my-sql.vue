<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr-on4bcb.css';
import '../../css/u/ubjsthbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr-on4bcb"/><path class="ubjsthbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:my-sql" /></template>
