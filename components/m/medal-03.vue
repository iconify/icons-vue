<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/p7q04xb2q.css';
import '../../css/r/rc38l5tfq.css';
import '../../css/g/g9bnktb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="p7q04xb2q"/><path class="rc38l5tfq"/><path class="g9bnktb9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:medal-03" /></template>
