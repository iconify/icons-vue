<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml_yo8qyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml_yo8qyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:open-bug-bounty" /></template>
