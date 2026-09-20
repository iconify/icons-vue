<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aigr65bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aigr65bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nf-core" /></template>
