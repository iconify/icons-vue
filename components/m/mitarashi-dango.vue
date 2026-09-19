<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk6pn-bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk6pn-bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:mitarashi-dango" /></template>
