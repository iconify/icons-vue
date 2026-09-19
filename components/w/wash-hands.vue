<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz14lmj4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zz14lmj4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:wash-hands" /></template>
