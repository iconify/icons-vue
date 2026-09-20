<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ploysl_qi.css';
import '../../css/j/jlgzaobtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ploysl_qi"/><path class="jlgzaobtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:piefed" /></template>
