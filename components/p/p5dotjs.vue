<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siwlnswnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="siwlnswnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:p5dotjs" /></template>
