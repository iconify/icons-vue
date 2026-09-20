<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdz5_tljs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hdz5_tljs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:prescription-pills-drugs-healthcare-solid" /></template>
