<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcs0clwsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcs0clwsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-vertical-sharp-fill" /></template>
