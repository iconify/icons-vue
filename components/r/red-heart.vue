<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk5-ttbbm.css';
import '../../css/t/tqz5znvkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="qk5-ttbbm"/><path class="tqz5znvkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:red-heart" /></template>
