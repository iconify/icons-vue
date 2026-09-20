<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxbf69ndo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rxbf69ndo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:mug" /></template>
