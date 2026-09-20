<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qllzi2dkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qllzi2dkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vertical-slot" /></template>
