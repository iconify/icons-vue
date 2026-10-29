<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elpcvs6hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elpcvs6hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shuffle-solid" /></template>
