<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/eio-gbbes.css';
import '../../css/r/rp04lyous.css';
import '../../css/n/no4wsvg0e.css';
import '../../css/z/zv90_cths.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eio-gbbes"/><path clip-rule="evenodd" class="rp04lyous"/><path class="no4wsvg0e"/><path clip-rule="evenodd" class="zv90_cths"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:notification-circle" /></template>
