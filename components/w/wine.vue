<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm9h6ul1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm9h6ul1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wine" /></template>
