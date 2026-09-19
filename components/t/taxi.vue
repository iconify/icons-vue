<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiasnzb7m.css';
import '../../css/k/kai3g5bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qiasnzb7m"/><path class="kai3g5bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:taxi" /></template>
