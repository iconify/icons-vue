<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuqt_yb-q.css';
import '../../css/k/kgyn-hblg.css';
import '../../css/d/ddohpfdpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuqt_yb-q"/><path class="kgyn-hblg"/><path class="ddohpfdpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:times-circle" /></template>
