<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkmclvb3d.css';
import '../../css/a/acxt2achp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkmclvb3d"/><path class="acxt2achp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:product-management" /></template>
