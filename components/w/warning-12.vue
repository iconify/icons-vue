<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skrsffb9p.css';
import '../../css/q/qll572bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="skrsffb9p"/><path clip-rule="evenodd" class="qll572bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:warning-12" /></template>
