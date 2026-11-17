<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/s/skzq3efbt.css';
import '../../css/p/p4ojfpbms.css';
import '../../css/b/bv8sd55gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="skzq3efbt"/><path class="p4ojfpbms"/><path class="bv8sd55gu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:paintbrush" /></template>
