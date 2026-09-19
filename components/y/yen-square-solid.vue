<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_93w0w3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_93w0w3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:yen-square-solid" /></template>
