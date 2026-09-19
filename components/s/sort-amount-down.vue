<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_s4ql23r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j_s4ql23r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sort-amount-down" /></template>
