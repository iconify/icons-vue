<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8d66nlfs.css';
import '../../css/p/phox42bnd.css';
import '../../css/r/rmb7iccqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j8d66nlfs"/><path class="phox42bnd"/><path class="rmb7iccqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monitor-off-48-bold" /></template>
