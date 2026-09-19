<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbdr4jq1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="cbdr4jq1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-stack-3d-down-dottedline" /></template>
