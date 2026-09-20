<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0zhpp2bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0zhpp2bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sharp" /></template>
