<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhfg48bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhfg48bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:square-full" /></template>
