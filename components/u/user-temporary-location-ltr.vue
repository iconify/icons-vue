<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhdtu4l9b.css';
import '../../css/h/hzbrfoizy.css';
import '../../css/d/do_17v_nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zhdtu4l9b"/><path class="hzbrfoizy"/><circle class="do_17v_nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-temporary-location-ltr" /></template>
