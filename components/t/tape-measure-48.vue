<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow6zdh7dh.css';
import '../../css/m/m0tcvtbkn.css';
import '../../css/g/g179ywr-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ow6zdh7dh"/><path class="m0tcvtbkn"/><path class="g179ywr-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tape-measure-48" /></template>
