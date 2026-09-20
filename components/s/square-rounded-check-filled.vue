<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dneqeub1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dneqeub1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-check-filled" /></template>
