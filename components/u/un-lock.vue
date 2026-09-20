<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxg-_if6l.css';
import '../../css/z/zngdjrb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qxg-_if6l"/><path class="zngdjrb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:un-lock" /></template>
