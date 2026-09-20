<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edils5bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edils5bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:v2ex" /></template>
