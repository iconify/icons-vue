<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifoyfinjb.css';
import '../../css/p/pxi__8h-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ifoyfinjb"/><path clip-rule="evenodd" class="pxi__8h-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:stack-remove-16" /></template>
