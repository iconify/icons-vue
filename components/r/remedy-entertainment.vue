<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vthu1k3km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vthu1k3km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:remedy-entertainment" /></template>
