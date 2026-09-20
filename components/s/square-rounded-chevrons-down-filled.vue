<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4dzfdc3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4dzfdc3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-chevrons-down-filled" /></template>
