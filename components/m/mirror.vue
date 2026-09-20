<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggcpgirks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ggcpgirks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:mirror" /></template>
