<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc0a1acff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gc0a1acff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vault" /></template>
