<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxs9r3b1f.css';
import '../../css/r/rige9ccms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zxs9r3b1f"/><path class="rige9ccms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:scala" /></template>
