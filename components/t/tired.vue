<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmu3bk6pi.css';
import '../../css/b/bwibdw4bb.css';
import '../../css/l/lenv5cbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmu3bk6pi"/><path class="bwibdw4bb"/><path class="lenv5cbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tired" /></template>
