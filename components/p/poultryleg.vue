<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj6jfsbht.css';
import '../../css/z/zalemybnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wj6jfsbht"/><path class="zalemybnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:poultryleg" /></template>
