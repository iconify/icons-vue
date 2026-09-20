<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_hxwwbci.css';
import '../../css/n/nd9qslmdc.css';
import '../../css/q/q9vu7mxpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_hxwwbci"/><path class="nd9qslmdc"/><path class="q9vu7mxpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:task-marked-filled" /></template>
