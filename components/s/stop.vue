<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui3x2lbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ui3x2lbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:stop" /></template>
