<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2u9f_tut.css';
import '../../css/e/ezgs73y2p.css';
import '../../css/z/ze96stecn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n2u9f_tut"/><path class="ezgs73y2p"/><path class="ze96stecn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rugby-48" /></template>
