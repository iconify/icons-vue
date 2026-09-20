<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u53jmomkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u53jmomkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone4" /></template>
