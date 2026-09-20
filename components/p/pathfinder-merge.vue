<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee3nxnbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ee3nxnbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pathfinder-merge" /></template>
