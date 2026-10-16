<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd6f3jb2l.css';
import '../../css/p/pycxazbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rd6f3jb2l"/><path class="pycxazbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tank-farm-20" /></template>
