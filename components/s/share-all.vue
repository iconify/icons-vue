<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn79_h0_p.css';
import '../../css/q/qt5cq3bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cn79_h0_p"/><path class="qt5cq3bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:share-all" /></template>
