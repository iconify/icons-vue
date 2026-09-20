<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeg-4mxue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oeg-4mxue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:verified" /></template>
