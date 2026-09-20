<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd7sdd_nh.css';
import '../../css/v/v8fd06b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="qd7sdd_nh"/><path class="v8fd06b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:maple-leaf" /></template>
