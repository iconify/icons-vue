<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw0v0acxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pw0v0acxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:waterfall-into-water" /></template>
