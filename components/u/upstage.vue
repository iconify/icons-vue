<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjs2o5y2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjs2o5y2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:upstage" /></template>
