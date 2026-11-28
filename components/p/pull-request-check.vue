<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbxs4bbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbxs4bbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pull-request-check" /></template>
