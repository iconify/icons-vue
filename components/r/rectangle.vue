<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk94mmbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jk94mmbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:rectangle" /></template>
