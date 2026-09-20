<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae_8ftbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ae_8ftbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-bar-chart-horizontal-start-sharp-fill" /></template>
