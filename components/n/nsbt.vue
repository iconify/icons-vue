<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-4pu_zsf.css';
import '../../css/i/iqgs3ioxp.css';
import '../../css/w/wwby37bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x-4pu_zsf"/><path class="iqgs3ioxp"/><path class="wwby37bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nsbt" /></template>
