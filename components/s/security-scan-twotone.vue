<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm3xmebmn.css';
import '../../css/x/x6zdh-elq.css';
import '../../css/k/kghrh9bow.css';
import '../../css/w/wjl1hub3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qm3xmebmn"/><path class="x6zdh-elq"/><path class="kghrh9bow"/><path class="wjl1hub3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:security-scan-twotone" /></template>
