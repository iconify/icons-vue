<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzwkyi3nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzwkyi3nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:microwave" /></template>
