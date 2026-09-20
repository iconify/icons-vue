<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukhdugxpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukhdugxpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:open-badges" /></template>
