<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itz8c4-rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itz8c4-rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:s7-airlines" /></template>
