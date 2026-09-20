<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onpdv5bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onpdv5bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:zoom-out" /></template>
