<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtgj7rfhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jtgj7rfhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-bar-chart-2-down-fill" /></template>
