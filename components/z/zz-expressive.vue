<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uojnhyalb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uojnhyalb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:zz-expressive" /></template>
