<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsgp-8odn.css';
import '../../css/z/zs1_24dzp.css';
import '../../css/x/xnni9p8to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xsgp-8odn"/><path class="zs1_24dzp"/><path class="xnni9p8to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:recloser-48" /></template>
