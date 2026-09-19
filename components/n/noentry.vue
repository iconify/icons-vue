<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6pzuyx4r.css';
import '../../css/u/ufqy7fo2b.css';
import '../../css/x/xw_4jzbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="t6pzuyx4r"/><path class="ufqy7fo2b"/><path class="xw_4jzbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:noentry" /></template>
