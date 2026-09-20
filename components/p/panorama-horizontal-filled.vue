<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxh_3bcls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxh_3bcls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:panorama-horizontal-filled" /></template>
