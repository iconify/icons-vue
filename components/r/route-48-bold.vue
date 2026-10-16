<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb93embdy.css';
import '../../css/j/jmov7dbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lb93embdy"/><path class="jmov7dbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:route-48-bold" /></template>
