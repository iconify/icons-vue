<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah766zb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah766zb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:roon" /></template>
