<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz3f5jbrh.css';
import '../../css/y/yszcp8i3o.css';
import '../../css/b/bhdojms-k.css';
import '../../css/m/mj_kz-61s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="dz3f5jbrh"/><path class="yszcp8i3o"/><path class="bhdojms-k"/><path class="mj_kz-61s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:podcast" /></template>
