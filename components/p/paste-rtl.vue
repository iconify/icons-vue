<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl12y3b3s.css';
import '../../css/g/grg2vfnmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pl12y3b3s"/><path class="grg2vfnmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:paste-rtl" /></template>
