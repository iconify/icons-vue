<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe2119bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe2119bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:server-check" /></template>
