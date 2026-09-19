<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_xre-9eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_xre-9eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:plane" /></template>
