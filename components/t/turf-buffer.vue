<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xubdi0bqd.css';
import '../../css/w/wkhlrxb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="xubdi0bqd"/><path class="wkhlrxb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-buffer" /></template>
