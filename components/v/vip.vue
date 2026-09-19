<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkmbsbbqu.css';
import '../../css/k/kb1ytkvcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jkmbsbbqu"/><path class="kb1ytkvcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:vip" /></template>
