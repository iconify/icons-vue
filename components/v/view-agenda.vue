<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztiienbai.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p_3zmsvya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGoWCmBljB" class="ztiienbai"/></defs><g class="ft5dv1b6b"><use href="#SVGoWCmBljB"/><use href="#SVGoWCmBljB" class="p_3zmsvya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:view-agenda" /></template>
