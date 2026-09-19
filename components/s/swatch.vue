<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfkacmblt.css';
import '../../css/q/qww1sgbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfkacmblt"/><path class="qww1sgbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:swatch" /></template>
