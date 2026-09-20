<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq25kzbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq25kzbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pretzel" /></template>
