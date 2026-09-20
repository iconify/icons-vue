<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn5qy_bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dn5qy_bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mouse-right-click-outline" /></template>
