<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecuu_-sxs.css';
import '../../css/j/j6ag-3bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecuu_-sxs"/><path class="j6ag-3bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:warning-outline" /></template>
