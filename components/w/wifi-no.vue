<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8juht2-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8juht2-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:wifi-no" /></template>
