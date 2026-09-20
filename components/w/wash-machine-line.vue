<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2_0eeu6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2_0eeu6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wash-machine-line" /></template>
