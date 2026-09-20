<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pige5ykcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pige5ykcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:three-quarters-circle-dash-line" /></template>
