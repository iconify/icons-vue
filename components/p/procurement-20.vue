<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvm_9zb2m.css';
import '../../css/w/wx5f8bcnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jvm_9zb2m"/><path class="wx5f8bcnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:procurement-20" /></template>
