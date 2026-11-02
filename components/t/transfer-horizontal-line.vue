<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ook-wzb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ook-wzb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transfer-horizontal-line" /></template>
