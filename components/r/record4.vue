<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to4no2b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to4no2b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:record4" /></template>
