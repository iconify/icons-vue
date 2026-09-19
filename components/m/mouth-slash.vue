<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfe3hlzex.css';
import '../../css/n/ncinpdbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kfe3hlzex"/><path class="ncinpdbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:mouth-slash" /></template>
