<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0xlczgvc.css';
import '../../css/s/syzigfb3q.css';
import '../../css/j/j_a6aebui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o0xlczgvc"/><path class="syzigfb3q"/><path class="j_a6aebui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:monero" /></template>
