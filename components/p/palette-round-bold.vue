<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcsc5yb1p.css';
import '../../css/y/yftbzgjri.css';
import '../../css/e/elfm62bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcsc5yb1p"/><path class="yftbzgjri"/><path clip-rule="evenodd" class="elfm62bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:palette-round-bold" /></template>
