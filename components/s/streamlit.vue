<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovu3qlb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovu3qlb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:streamlit" /></template>
