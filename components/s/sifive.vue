<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4u8f2b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4u8f2b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sifive" /></template>
