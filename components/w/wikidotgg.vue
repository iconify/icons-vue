<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3_iv84nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3_iv84nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wikidotgg" /></template>
