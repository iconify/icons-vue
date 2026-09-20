<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziao2px2e.css';
import '../../css/h/hyv-2gbfp.css';
import '../../css/k/k9mgxccva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ziao2px2e"/><path class="hyv-2gbfp"/><path class="k9mgxccva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:taskfile" /></template>
