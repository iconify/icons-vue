<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8l77y5we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8l77y5we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-chevron-right-filled" /></template>
