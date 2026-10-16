<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewic4fbqt.css';
import '../../css/k/kunjmdq2f.css';
import '../../css/j/ja15efbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ewic4fbqt"/><path class="kunjmdq2f"/><path class="ja15efbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:synchronous-condenser-20-bold" /></template>
