<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kji6v2qse.css';
import '../../css/z/ztfq1ibst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kji6v2qse"/><path class="ztfq1ibst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:screen-mirroring-filled" /></template>
