<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfmc3nbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfmc3nbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:taipei101-line" /></template>
