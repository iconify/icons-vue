<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzla5f-tc.css';
import '../../css/g/gw3y6so7m.css';
import '../../css/n/noxr8smkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzla5f-tc"/><path class="gw3y6so7m"/><path class="noxr8smkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rainbow" /></template>
