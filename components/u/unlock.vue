<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzl7znbzk.css';
import '../../css/u/uqsh6ibhf.css';
import '../../css/p/pr87757ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qzl7znbzk"/><path class="uqsh6ibhf"/><circle class="pr87757ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:unlock" /></template>
