<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx5ltho2y.css';
import '../../css/x/xoymbvb-h.css';
import '../../css/l/lmotn3buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kx5ltho2y"/><path class="xoymbvb-h"/><path class="lmotn3buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:no-video" /></template>
