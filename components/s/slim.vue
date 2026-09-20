<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y73fl8hsz.css';
import '../../css/f/f21qp2hxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="y73fl8hsz"/><path class="f21qp2hxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:slim" /></template>
