<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmfqwbbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmfqwbbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:map-marker-info" /></template>
