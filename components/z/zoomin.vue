<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csah_sx9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="csah_sx9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:zoomin" /></template>
