<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qodg3fqvb.css';
import '../../css/o/o32ailbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qodg3fqvb"/><path class="o32ailbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:umbrella-20-bold" /></template>
