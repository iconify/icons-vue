<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw-ghd7bo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="hw-ghd7bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:recycling-11" /></template>
