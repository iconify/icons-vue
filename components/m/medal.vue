<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfs19bcvf.css';
import '../../css/a/an4c_3b3j.css';
import '../../css/y/yjo7ewdyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="xfs19bcvf"/><path class="an4c_3b3j"/><path class="yjo7ewdyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:medal" /></template>
