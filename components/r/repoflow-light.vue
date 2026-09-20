<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dibcotb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dibcotb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:repoflow-light" /></template>
