<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9ltyhbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9ltyhbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:traffic-cone-line" /></template>
