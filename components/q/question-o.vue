<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xri8-yvdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xri8-yvdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:question-o" /></template>
