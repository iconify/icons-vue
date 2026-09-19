<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj0mwubcb.css';
import '../../css/q/qm3xmebmn.css';
import '../../css/s/s-rrjubfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oj0mwubcb"/><path class="qm3xmebmn"/><path class="s-rrjubfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:verified-outlined" /></template>
